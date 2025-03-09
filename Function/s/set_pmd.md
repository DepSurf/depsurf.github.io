# Function: <code>set_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594975928,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_cleanhighmap",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995603,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060220,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220909,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358450,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:pmd_clear",
        "arch/x86/mm/init_64.c:ident_pmd_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595065061,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288215,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309025,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316210,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580667476,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:__pte_alloc_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746801,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361688,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891403,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:514",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595142087,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_cleanhighmap",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992348,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056575,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579221139,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851316,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595230784,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289568,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308752,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321787,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580787812,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580866017,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863136,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032974,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051265,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580059,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:487",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384757,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_cleanhighmap",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994188,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055593,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233293,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066079,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595473841,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304992,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323984,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337019,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580852100,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907985,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077842,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108148,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134036,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764731,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578965971,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596306096,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047839,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230889,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292881,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395403,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302732,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321345,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331007,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897744,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953441,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304295,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146721,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174283,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888019,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602595010,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969947,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602624032,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056668,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246486,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588857981,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602714471,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324290,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344548,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356515,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602722988,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996285,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055185,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869630,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281255,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307661,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376843,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763340,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972545,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792730,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061613,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579258929,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237128,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602887110,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335122,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356442,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368925,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602895256,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130380,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193905,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248654,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429795,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581452926,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680715,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557433,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970658,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586595,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066189,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282593,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481166,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684120,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361666,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383595,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396381,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579411387,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209544,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267088,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277185,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278779,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490940,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494709,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524325,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535522,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041151,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190117,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811451,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820681,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651767,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977666,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681985,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074733,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296857,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940898,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604783658,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376239,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399068,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411705,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579427088,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283936,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341666,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351634,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354655,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951904,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602625,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633240,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645628,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202241,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353484,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588117163,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123785,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604664039,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980066,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694427,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076733,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302409,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168450,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809425,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579380527,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402380,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414889,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579430317,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342656,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400992,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411138,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414182,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487968,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179438,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673313,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704280,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717302,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283078,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452380,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322795,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328585,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015251,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988342,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071579018338,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ]
    },
    {
      "addr": 18446744071579087679,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332370,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591184317,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:pmd_clear"
      ]
    },
    {
      "addr": 18446744071609148105,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411753,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419214,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444477,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579455830,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517976,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597313,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_normal_pmd",
        "mm/mremap.c:move_normal_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611250,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613825,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694295,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197739,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891840,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920310,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936176,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570793,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748498,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591143109,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150889,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987808,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579018338,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393629,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077255,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989830,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071591242686,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ]
    },
    {
      "addr": 18446744071579089743,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333954,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591679670,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071612218447,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412463,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419886,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442078,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591273082,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563683,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643497,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658582,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662219,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739154,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692630,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937900,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966994,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978692,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643113,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820745,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226869,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236873,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989296,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591242686,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266319,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215762,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999225,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071591185776,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ]
    },
    {
      "addr": 18446744071579096304,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336650,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398104,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071591212973,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579415583,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422506,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444957,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216030,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320078,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604892,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665000,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581680390,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684140,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767448,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275901,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581963397,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581995117,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071582006713,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671126,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849517,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591176109,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179539,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998256,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185776,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208630,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581964752,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134603,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016905,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071592047948,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ]
    },
    {
      "addr": 18446744071579119452,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391963,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460328,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071592087323,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579478463,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486134,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509757,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092720,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565502,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871084,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933574,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581949670,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953352,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050106,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170672,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582297309,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309147,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997382,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182573,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592029805,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035618,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:438",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015936,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592047948,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082268,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897915,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036067,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071593814425,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ]
    },
    {
      "addr": 18446744071579152019,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458468,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536269,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071593854150,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579557037,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579565918,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593168,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859856,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593969833,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582265507,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342517,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582359140,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582364229,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481217,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582628862,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785144,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry"
      ]
    },
    {
      "addr": 18446744071582805320,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468744,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583673724,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593797639,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593801062,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034608,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593814425,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579532480,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582745824,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627491723,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064730,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627540032,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200346,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547624,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438471,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654268,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579664083,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674081,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704542,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716999,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625707,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582756949,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843803,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582861444,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867779,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582995171,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583118507,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583153051,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583318166,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry"
      ]
    },
    {
      "addr": 18446744071583338922,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061538,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281273,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595741744,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746826,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278640,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619235851,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064602,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619286202,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204390,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562920,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596979302,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668332,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579678227,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687954,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718037,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730567,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834795,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582972758,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060235,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583076948,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085127,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583204502,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328779,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583363483,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583536683,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry"
      ]
    },
    {
      "addr": 18446744071583558043,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287974,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584511357,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596267712,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596271108,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583498096,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621525931,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090554,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578698,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233734,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590456,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597907734,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621772562,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712371,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722482,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752566,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765511,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009243,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583150515,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241707,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583259204,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267738,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583440273,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565115,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583599963,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583730625,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071583757902,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504774,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584733987,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597150400,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155844,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691248,
      "name": "set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490349608,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:pmd_clear_huge",
        "arch/arm64/mm/mmu.c:pmd_set_huge",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:early_fixmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490464092,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:__unmap_hyp_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492748752,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492810140,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503922324,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129344,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493164864,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:469",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:138",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272732334,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272772710,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:138",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270897228,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590311,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980418,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620708,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077085,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298217,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770738,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723367,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376431,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398284,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410729,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579426157,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311504,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369840,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379986,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383030,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456816,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781726,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642049,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673016,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686038,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251814,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421116,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926443,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935369,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668135,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980002,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698523,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076669,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579299417,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214146,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800934,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376351,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398204,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410649,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579426077,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302704,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361040,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371186,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374230,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448016,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225134,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633361,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664328,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677350,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242294,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411596,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259851,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267145,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
  "name": "set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668140,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980594,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698529,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080765,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579308249,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590264514,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:pmd_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813553,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384831,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406700,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419513,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579435261,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366684,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424929,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435074,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438511,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513506,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275492,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699697,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730696,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744013,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319884,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491042,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395371,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402313,
      "name": "set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:453",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
void set_pmd(pmd_t * pmdp, pmd_t pmd)
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

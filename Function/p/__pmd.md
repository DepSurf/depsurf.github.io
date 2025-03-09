# Function: <code>__pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594975871,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
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
      "addr": 18446744071578995583,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060115,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220889,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358435,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
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
      "addr": 18446744071595065044,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288198,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
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
      "addr": 18446744071579309013,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316200,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580667464,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
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
      "addr": 18446744071580746789,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad",
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361671,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890073,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891382,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437820,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:525",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595142072,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
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
      "addr": 18446744071578992335,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056493,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579221126,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851303,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
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
      "addr": 18446744071595230774,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289558,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
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
      "addr": 18446744071579308737,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321777,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580787465,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580866556,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863126,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020602,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032961,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050657,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620268,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580027,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:498",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384742,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071578994175,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055511,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233280,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066066,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071595473831,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304982,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071579323969,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337009,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580851761,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908492,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077832,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095202,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108138,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133611,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585169,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708662,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764699,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578965958,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596306084,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
      "addr": 18446744071579047753,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230879,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292868,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
      "addr": 18446744071596395393,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302722,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
      "addr": 18446744071579321330,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330997,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897066,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954044,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955259,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304285,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142003,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146711,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:touch_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173753,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646094,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755540,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586887987,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602595000,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969937,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602624020,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071579056582,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246476,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588857968,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071602714461,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324280,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071579344533,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356505,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602722978,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995620,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071581055173,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869620,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264242,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293647,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307648,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791673,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376811,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763326,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972517,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792720,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071579061504,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579258905,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237115,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071602887086,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335109,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071579356432,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071579368911,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602895231,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129707,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071581194560,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248630,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411222,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440756,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451727,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964167,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587680681,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557419,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970630,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586585,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
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
      "addr": 18446744071579066080,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282569,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481153,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pmd_init",
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
      "addr": 18446744071604684096,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361653,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
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
      "addr": 18446744071579383585,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
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
      "addr": 18446744071579396367,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579411362,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209454,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
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
      "addr": 18446744071581267069,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277936,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490916,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494649,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524177,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535378,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048808,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587811417,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820666,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651753,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977635,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681975,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
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
      "addr": 18446744071579074624,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296833,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940885,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
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
      "addr": 18446744071604783634,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376226,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
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
      "addr": 18446744071579399058,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
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
      "addr": 18446744071579411691,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579427063,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283908,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
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
      "addr": 18446744071581341643,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352409,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951880,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602566,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633107,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645442,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205735,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588117129,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123770,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604664025,
      "name": "__pmd",
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
      "addr": 18446744071578980035,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694417,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579076624,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302385,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168437,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071604809401,
      "name": "__pmd",
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
      "addr": 18446744071579380514,
      "name": "__pmd",
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
      "addr": 18446744071579402370,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579414875,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579430292,
      "name": "__pmd",
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
      "addr": 18446744071581342628,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071581400969,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411913,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179414,
      "name": "__pmd",
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
      "addr": 18446744071581673254,
      "name": "__pmd",
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
      "addr": 18446744071581704147,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717116,
      "name": "__pmd",
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
      "addr": 18446744071582286583,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588322761,
      "name": "__pmd",
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
      "addr": 18446744071588328570,
      "name": "__pmd",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t __pmd(pmdval_t val)
```

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015234,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988317,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
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
      "addr": 18446744071579018351,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579087571,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332346,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591184293,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
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
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:pmd_clear"
      ]
    },
    {
      "addr": 18446744071609148081,
      "name": "__pmd",
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
      "addr": 18446744071579411743,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
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
      "addr": 18446744071579419201,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
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
      "addr": 18446744071579444449,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence",
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579455805,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517863,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
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
      "addr": 18446744071581597294,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_normal_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612040,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197715,
      "name": "__pmd",
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
      "addr": 18446744071581891782,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920176,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936052,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575991,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591143074,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150871,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:478",
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
      "addr": 18446744071578987824,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579018351,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393642,
      "name": "__pmd",
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
pmd_t __pmd(pmdval_t val)
```

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077238,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989805,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
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
      "addr": 18446744071591242699,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579089635,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333930,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591679646,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
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
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071612218423,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419873,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442050,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence",
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591273057,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563577,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659368,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692606,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937842,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966864,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978571,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647401,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591226834,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236855,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:420",
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
      "addr": 18446744071578989312,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591242699,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266332,
      "name": "__pmd",
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
pmd_t __pmd(pmdval_t val)
```

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215745,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999200,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
      "addr": 18446744071591185789,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579096196,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336625,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398078,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071591212948,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579422496,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444929,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence",
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216005,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320050,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603947,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": [
        "mm/memory.c:finish_fault"
      ]
    },
    {
      "addr": 18446744071581680024,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275876,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581963339,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994963,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006592,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673710,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591176074,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179521,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
      "addr": 18446744071578998272,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185789,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208643,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581581904,
      "name": "__pmd",
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
pmd_t __pmd(pmdval_t val)
```

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134586,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016880,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
      "addr": 18446744071592047961,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579119329,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391938,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460302,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071592087298,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579486124,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509729,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence",
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092695,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565474,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857980,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": [
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_set_pmd"
      ]
    },
    {
      "addr": 18446744071581933678,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581949304,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170647,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582297155,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309019,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999998,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592029770,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035600,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
      "addr": 18446744071579015952,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592047961,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082281,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581846864,
      "name": "__pmd",
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
pmd_t __pmd(pmdval_t val)
```

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897899,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036044,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
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
      "addr": 18446744071593814463,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579151899,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458444,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536244,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:ident_pmd_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071593854126,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579555293,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579565912,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593155,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859832,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593969809,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582265407,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342618,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582358690,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582628838,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582784983,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582805208,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468735,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593797602,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593801045,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
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
      "addr": 18446744071579034656,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071593814463,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579532528,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491710,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064710,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627540024,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200226,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547603,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438462,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
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
      "addr": 18446744071579654247,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579662112,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674075,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704572,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716978,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625686,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582756834,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843899,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582860917,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583118486,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583153030,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583317944,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338802,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061532,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595741717,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746812,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235838,
      "name": "__pmd",
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
      "addr": 18446744071579064582,
      "name": "__pmd",
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
      "addr": 18446744071619286194,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204273,
      "name": "__pmd",
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
      "addr": 18446744071579562899,
      "name": "__pmd",
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
      "addr": 18446744071596979293,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
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
      "addr": 18446744071579668311,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579676296,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687948,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718060,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730546,
      "name": "__pmd",
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
      "addr": 18446744071582834774,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582972648,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060331,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583077986,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328758,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583363462,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583536457,
      "name": "__pmd",
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
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557910,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287968,
      "name": "__pmd",
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
      "addr": 18446744071596267685,
      "name": "__pmd",
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
      "addr": 18446744071596271094,
      "name": "__pmd",
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
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t __pmd(pmdval_t val)
```

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621525918,
      "name": "__pmd",
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
      "addr": 18446744071579090534,
      "name": "__pmd",
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
      "addr": 18446744071621578690,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233617,
      "name": "__pmd",
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
      "addr": 18446744071579590435,
      "name": "__pmd",
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
      "addr": 18446744071597907725,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
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
      "addr": 18446744071621772541,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710424,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722476,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752629,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence",
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765490,
      "name": "__pmd",
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
      "addr": 18446744071583009222,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583150399,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241803,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583260242,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565094,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583599942,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583730377,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:pmd_modify"
      ],
      "caller_func": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583757738,
      "name": "__pmd",
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
      "addr": 18446744071584504768,
      "name": "__pmd",
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
      "addr": 18446744071597150373,
      "name": "__pmd",
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
      "addr": 18446744071597155830,
      "name": "__pmd",
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
      "addr": 18446744071583691312,
      "name": "__pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590297,
      "name": "__pmd",
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
      "addr": 18446744071578980387,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620698,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579076976,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298193,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770725,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071604723343,
      "name": "__pmd",
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
      "addr": 18446744071579376418,
      "name": "__pmd",
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
      "addr": 18446744071579398274,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579410715,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579426132,
      "name": "__pmd",
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
      "addr": 18446744071581311476,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071581369817,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380761,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781702,
      "name": "__pmd",
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
      "addr": 18446744071581641990,
      "name": "__pmd",
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
      "addr": 18446744071581672883,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685852,
      "name": "__pmd",
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
      "addr": 18446744071582255319,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587926409,
      "name": "__pmd",
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
      "addr": 18446744071587935354,
      "name": "__pmd",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668121,
      "name": "__pmd",
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
      "addr": 18446744071578979971,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698513,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579076560,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579299393,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214133,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071604800910,
      "name": "__pmd",
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
      "addr": 18446744071579376338,
      "name": "__pmd",
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
      "addr": 18446744071579398194,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579410635,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579426052,
      "name": "__pmd",
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
      "addr": 18446744071581302676,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071581361017,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371961,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225110,
      "name": "__pmd",
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
      "addr": 18446744071581633302,
      "name": "__pmd",
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
      "addr": 18446744071581664195,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677164,
      "name": "__pmd",
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
      "addr": 18446744071582245799,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588259817,
      "name": "__pmd",
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
      "addr": 18446744071588267130,
      "name": "__pmd",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668126,
      "name": "__pmd",
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
      "addr": 18446744071578980563,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698519,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579080656,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579308225,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590264501,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071604813529,
      "name": "__pmd",
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
      "addr": 18446744071579384818,
      "name": "__pmd",
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
      "addr": 18446744071579406690,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071579419499,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579435236,
      "name": "__pmd",
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
      "addr": 18446744071581366656,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
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
      "addr": 18446744071581424906,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435849,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275468,
      "name": "__pmd",
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
      "addr": 18446744071581699638,
      "name": "__pmd",
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
      "addr": 18446744071581730563,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743827,
      "name": "__pmd",
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
      "addr": 18446744071582328588,
      "name": "__pmd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:464",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588395337,
      "name": "__pmd",
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
      "addr": 18446744071588402298,
      "name": "__pmd",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
pmd_t __pmd(pmdval_t val)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
pmd_t __pmd(pmdval_t val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
pmd_t __pmd(pmdval_t val)
```
</details>
</li>
</ul>

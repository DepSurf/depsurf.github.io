# Function: <code>pfn_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958160,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578967728,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071578994192,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071595008933,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220975,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358462,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    },
    {
      "addr": 18446744071595065274,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288426,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308357,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:native_set_fixmap",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:pmd_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448871,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661760,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580737229,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580763564,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790632,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587361413,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833863,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880162,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907093,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973486,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953649,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583920128,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:354",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958160,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578967728,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578994192,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579358462,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580661760,
      "name": "pfn_pte",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578959300,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578968267,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071578992498,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071595173583,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221206,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365339,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071595230997,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294451,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308455,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580524159,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580793113,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855054,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580886085,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913898,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587862849,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959775,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007770,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033356,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128756,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241220,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584251349,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955072,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578964640,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578990800,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579365339,
      "name": "pfn_pte",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961364,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578970043,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071578994338,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071595415963,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233360,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383435,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071595474054,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309951,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323687,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587498,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580852422,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580925187,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580954172,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982487,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588077555,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033265,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081789,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108541,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203826,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356532,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432962,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:383",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956912,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578966464,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578992640,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579383435,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580836288,
      "name": "pfn_pte",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966069,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071578973492,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578978159,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071596335077,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230956,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291260,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071596395606,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307929,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321050,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617451,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580798613,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897275,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580969865,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580999375,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028997,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588304008,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080451,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130557,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147069,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252694,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517814,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205858,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:514",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964464,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071578969440,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071578975392,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579291260,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580913136,
      "name": "pfn_pte",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969274,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071578976379,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578983344,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579049422,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602652481,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246565,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311003,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071602714674,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330273,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344234,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348848,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    },
    {
      "addr": 18446744071602724761,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698186,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872114,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997855,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072349,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581110593,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581138693,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588869325,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191793,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244530,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281598,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384659,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927846,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588755031,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:529",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967744,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071578972816,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071578978576,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579311003,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579348848,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581240720,
      "name": "pfn_pte",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972135,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071578979167,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578986170,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579054172,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602822244,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259018,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322467,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071602887318,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340907,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355636,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360637,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602896193,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830593,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006018,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129883,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault"
      ]
    },
    {
      "addr": 18446744071581207679,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581246535,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279097,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589248324,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336923,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389997,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430134,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534726,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159039,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133153,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:546",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970400,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071578975568,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071578981280,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579322467,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071581109584,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578970264,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ]
    },
    {
      "addr": 18446744071578977375,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578995002,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579059318,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604617392,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282682,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346771,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604684328,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368256,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382820,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388157,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692426,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693502,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897850,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083303,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208928,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071581291861,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581330056,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361625,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589490610,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420741,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473693,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501893,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620715,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269855,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589368142,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:548",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968528,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071578973648,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071578979344,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579346771,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071581189616,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578977271,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578984351,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578999111,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579066883,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579080727,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604713566,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296958,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362474,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604783877,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383056,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398284,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403660,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604792531,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793517,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995361,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146288,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283381,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366439,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581439959,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581472925,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589951546,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530025,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588649,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611525,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733075,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480730,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824975,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975568,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578980640,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578986320,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579362474,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979671,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578986719,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579000615,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579069230,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579082728,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725868,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302510,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366714,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604809632,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387360,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401596,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406844,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818093,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604819238,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049362,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203824,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342101,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426183,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581504183,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581536941,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590179100,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594924,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652313,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682437,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806627,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585621434,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590051199,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977968,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578983040,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578988688,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579366714,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990006,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578996063,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579005303,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579076923,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579094092,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138847,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332483,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393877,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071609148309,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410964,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417427,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427303,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609155959,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157430,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232004,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394300,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539352,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628848,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711510,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745635,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591197405,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809530,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870265,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900979,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023217,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585044581,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345078,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:604",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987840,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071578993328,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071578998992,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579393877,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991494,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578997967,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579009671,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579079307,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095304,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251356,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334067,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591266505,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071612218651,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411609,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417459,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426999,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612226454,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227914,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274599,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437808,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582568,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range"
      ]
    },
    {
      "addr": 18446744071581672050,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696266,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759302,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792723,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591692308,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857146,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916395,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946505,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072350,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461124,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989328,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071578995248,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579000816,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071591266505,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071581559760,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579000246,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071579007376,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579020407,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579086268,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579101517,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591195118,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336762,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591208820,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071614359644,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414777,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420560,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430007,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614367701,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368683,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291257,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458219,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613154,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range"
      ]
    },
    {
      "addr": 18446744071581694248,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786303,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822659,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591635066,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892247,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941371,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972434,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097368,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344900,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998288,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579003888,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071591186003,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071591208820,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581583600,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579017940,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071579025424,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579038375,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579109350,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579125437,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060903,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392076,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592082458,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071615290322,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477657,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484112,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494187,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615299250,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615300227,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535547,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880190,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071581966424,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070079,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582109075,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582172516,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ]
    },
    {
      "addr": 18446744071582186951,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247115,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275123,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412052,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865220,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:574",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015968,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071579021584,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071592048175,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071592082458,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581849280,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582170416,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579037149,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071579044935,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579058894,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579140504,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159766,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827417,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458584,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593849760,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071617069795,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556111,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563401,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574546,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617079215,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617080293,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884467,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279822,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071582385056,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509628,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552648,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582631392,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ]
    },
    {
      "addr": 18446744071582646678,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718381,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744110,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582758421,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925182,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588151316,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:577",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034688,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579040144,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579046592,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071593849760,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071582241456,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071582628448,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579066691,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627533263,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090335,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184869,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209960,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271033,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547729,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438416,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627718798,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663039,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671049,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683235,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627732398,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627734513,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317678,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582772356,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071582892935,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028200,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067976,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583122212,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596455134,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166589,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245319,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275781,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583292334,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480839,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589545152,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:594",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732048,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579066563,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619279589,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084079,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188936,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215510,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277306,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563026,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596979232,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619476270,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677195,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685008,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697081,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619491639,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619493769,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518827,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973136,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte"
      ]
    },
    {
      "addr": 18446744071583108238,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237829,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583280904,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583332487,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596996464,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382573,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583464299,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492139,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583510733,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697016,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_pte_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589846736,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:595",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948720,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579091651,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621570485,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109871,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218152,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244804,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307322,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590562,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597907664,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621772878,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711323,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719520,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731609,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621788631,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621790729,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687730,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150831,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte"
      ]
    },
    {
      "addr": 18446744071583297207,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469717,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583518141,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583568502,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597925944,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622270,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660118,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683250,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701062,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583896357,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590183332,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:764",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127280,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282735144,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "arch/powerpc/mm/book3s64/hash_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282776688,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_set_huge",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pud_set_huge",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285670728,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285906176,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286104912,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286212160,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_page_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286343268,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286411112,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297817612,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286467856,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286559928,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286604652,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286798560,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297671860,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:609",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270612292,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "arch/riscv/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:get_pmd_virt",
        "arch/riscv/mm/init.c:create_pte_mapping",
        "arch/riscv/mm/init.c:get_pte_virt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272622292,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272732006,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272783524,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272852066,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272892564,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270897116,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272910738,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272949894,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024232,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279720374,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:187",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980023,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578987071,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579000967,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579069582,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579083080,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604652171,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298318,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362618,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604723574,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383264,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397500,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402684,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604731973,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733118,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018210,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172672,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310949,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395031,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581472919,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581505677,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589781388,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563660,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621049,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651173,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775363,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585383082,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653455,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978320,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578983392,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578989040,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579362618,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579002291,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579015719,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604619868,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234103,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293301,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604691353,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312059,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326947,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332101,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604699706,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700752,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964335,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119494,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254675,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337939,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581421590,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447981,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589504190,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505212,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562393,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589775,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713599,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589379264,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293301,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979607,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578986655,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579000551,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579069166,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579082664,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729934,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299518,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362538,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604801141,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383184,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397420,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402604,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809540,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810685,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009410,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581163872,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302149,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386231,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581464231,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581496989,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590224796,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554972,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612361,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642485,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766675,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585571834,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096831,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977904,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578982976,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578988624,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579362538,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980199,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ]
    },
    {
      "addr": 18446744071578987535,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578996839,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579073006,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579086760,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729980,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308350,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370970,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    },
    {
      "addr": 18446744071604813760,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391679,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405916,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411468,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822221,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604823395,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070661,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230144,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366144,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450551,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581528954,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581565389,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590275154,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620020,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679961,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708869,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835514,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679802,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590147087,
      "name": "pfn_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:565",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978496,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578983568,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071578989760,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579370970,
      "name": "pfn_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

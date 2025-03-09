# Function: <code>__pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977450,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059781,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220683,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358404,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:pud_clear",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288102,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308923,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667663,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746709,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800490,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361872,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:565",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595142193,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056161,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220923,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848427,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287707,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308652,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789245,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865925,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924058,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863351,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580101,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:538",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384863,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055182,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233077,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063240,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303099,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323884,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853610,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907893,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992402,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078057,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764773,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596306132,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047440,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230679,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588289921,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300843,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321244,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898754,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953349,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039922,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304510,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152574,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888061,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594898,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602624068,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056231,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246254,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855225,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322261,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344722,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602722128,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000874,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055093,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149849,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869864,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267723,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376895,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763232,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792766,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061176,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579258697,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589234380,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333108,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356145,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382825,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134481,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193813,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293321,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248850,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415258,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680763,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557325,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586631,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065752,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282361,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477936,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359524,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383327,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410394,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210913,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277093,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376345,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491136,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498087,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811499,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820484,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:510",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651659,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604682020,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074296,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296626,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937488,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374116,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398799,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426185,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287072,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351542,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487244,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952107,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606496,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588117211,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123588,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:511",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663931,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694462,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076296,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302178,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590165040,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378404,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402111,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429353,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345792,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411046,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551660,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179641,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677072,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322843,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328388,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
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
pud_t __pud(pudval_t val)
```

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015140,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018364,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579087333,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332138,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185244,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:pud_clear"
      ]
    },
    {
      "addr": 18446744071579411487,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420085,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454777,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542144,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611142,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762082,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197940,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896504,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591143157,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150920,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:513",
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
      "addr": 18446744071579018364,
      "name": "__pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393681,
      "name": "__pud",
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
pud_t __pud(pudval_t val)
```

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077144,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242712,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579089397,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333722,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591680597,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 0,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420757,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451641,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585382,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817422,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692831,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942696,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226917,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236904,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
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
      "addr": 18446744071591242712,
      "name": "__pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266371,
      "name": "__pud",
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
pud_t __pud(pudval_t val)
```

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215651,
      "name": "__pud",
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
      "addr": 18446744071591185815,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579095958,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336418,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397726,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 0,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579423349,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454106,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607625,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845329,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275731,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581967868,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591176157,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179570,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
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
      "addr": 18446744071591185815,
      "name": "__pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208682,
      "name": "__pud",
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
pud_t __pud(pudval_t val)
```

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134487,
      "name": "__pud",
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
      "addr": 18446744071592047987,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579119581,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391731,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459950,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 0,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579486968,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519500,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874745,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933209,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582136585,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216430,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582270556,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592029853,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035649,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
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
      "addr": 18446744071592047987,
      "name": "__pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082320,
      "name": "__pud",
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
pud_t __pud(pudval_t val)
```

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897804,
      "name": "__pud",
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
      "addr": 18446744071593814481,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579152144,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458240,
      "name": "__pud",
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
      "addr": 18446744071579535876,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 0,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579566849,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603620,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593969641,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582272966,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342103,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582585985,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593995155,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582751072,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593797686,
      "name": "__pud",
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
      "addr": 18446744071593801094,
      "name": "__pud",
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
      "addr": 18446744071593814481,
      "name": "__pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579532640,
      "name": "__pud",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491612,
      "name": "__pud",
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
      "addr": 18446744071627540076,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199881,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547397,
      "name": "__pud",
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
      "addr": 18446744071596435770,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675019,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716630,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625494,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582765046,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843372,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098025,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152838,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583284807,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595741801,
      "name": "__pud",
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
      "addr": 18446744071595746861,
      "name": "__pud",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235740,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619286246,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203929,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562693,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596976038,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688887,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730208,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834582,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582981436,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059791,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583307914,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363270,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583504728,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596267769,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596271143,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525820,
      "name": "__pud",
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
      "addr": 18446744071621578742,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233273,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590229,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597904470,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579723415,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765152,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009030,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583124575,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241423,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515503,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599750,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583699212,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597150457,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155879,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590203,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620743,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076648,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579297986,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589767328,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374308,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398015,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425193,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314640,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379894,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520396,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781929,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645808,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926491,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935172,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668027,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698558,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076232,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579299186,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590210736,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374228,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397935,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425113,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305840,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371094,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511708,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225337,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637120,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259899,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266948,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
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
  "name": "__pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668032,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698564,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080328,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579308018,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590261104,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382708,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406431,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434297,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369840,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434982,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576764,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275695,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702226,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395419,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402116,
      "name": "__pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
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
pud_t __pud(pudval_t val)
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
pud_t __pud(pudval_t val)
```
</details>
</li>
</ul>

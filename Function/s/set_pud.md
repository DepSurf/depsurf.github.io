# Function: <code>set_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977467,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059866,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220703,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358419,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
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
      "addr": 18446744071579288119,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
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
      "addr": 18446744071579308935,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667678,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746721,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800499,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361892,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595142206,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056229,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220936,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848439,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
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
      "addr": 18446744071579287717,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308664,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789258,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865937,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924101,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863361,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580131,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384876,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055250,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233090,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063252,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
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
      "addr": 18446744071579303109,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323896,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853623,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907905,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992445,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078067,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764803,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:517",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596306144,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047509,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230689,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588289933,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
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
      "addr": 18446744071579300853,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321256,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898767,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953361,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039965,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304520,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888091,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:536",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594908,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602624080,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056300,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246264,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855237,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
      "addr": 18446744071579322271,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344734,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602722138,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000884,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055105,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149898,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869874,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376925,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763246,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792779,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061284,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579258721,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589234392,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
      "addr": 18446744071579333132,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356157,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382849,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134505,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193825,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293340,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248874,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680786,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557339,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586644,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065860,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282385,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477974,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071579359548,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383339,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410418,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210937,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277105,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376364,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491160,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811522,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820499,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651673,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604682032,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074404,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296650,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937568,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
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
      "addr": 18446744071579374140,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398815,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426209,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287096,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351554,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487263,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952131,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588117234,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123603,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663945,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694474,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076404,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302202,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590165120,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071579378428,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402127,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429377,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345816,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411058,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551679,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179665,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322866,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328403,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
void set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015157,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609045030,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087449,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332162,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185268,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:pud_clear"
      ]
    },
    {
      "addr": 18446744071579411503,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420098,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
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
      "addr": 18446744071579454801,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542168,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611154,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762101,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197964,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591143180,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150938,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
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
      "addr": 18446744071579393668,
      "name": "set_pud",
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
void set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077161,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612108392,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089513,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333746,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591680621,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579412102,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421907,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451665,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585406,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642895,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658502,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810169,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692855,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226940,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236922,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
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
      "addr": 18446744071591266358,
      "name": "set_pud",
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
void set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215668,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614248073,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096074,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336443,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397752,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579415254,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424965,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454131,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607650,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664655,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581680310,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838597,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275756,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591176181,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179588,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
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
      "addr": 18446744071591208669,
      "name": "set_pud",
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
void set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134504,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615168195,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119698,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391756,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459976,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579478134,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488592,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519525,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874770,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935798,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949590,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129446,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216455,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592029877,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035667,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
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
      "addr": 18446744071592082307,
      "name": "set_pud",
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
void set_pud(pud_t * pudp, pud_t pud)
```

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897820,
      "name": "set_pud",
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
      "addr": 18446744071616934216,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152263,
      "name": "set_pud",
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
      "addr": 18446744071579458264,
      "name": "set_pud",
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
      "addr": 18446744071579535901,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579556676,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568602,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603644,
      "name": "set_pud",
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
      "addr": 18446744071593969665,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582272990,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344794,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359044,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576242,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593995179,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593797709,
      "name": "set_pud",
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
      "addr": 18446744071593801111,
      "name": "set_pud",
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
  "symbols": [
    {
      "addr": 18446744071579532592,
      "name": "set_pud",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491625,
      "name": "set_pud",
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
      "addr": 18446744071627540084,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200001,
      "name": "set_pud",
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
      "addr": 18446744071579547418,
      "name": "set_pud",
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
      "addr": 18446744071596432655,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663703,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676840,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716651,
      "name": "set_pud",
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
      "addr": 18446744071582625515,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582765067,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846075,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861332,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095130,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152859,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:462",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595741814,
      "name": "set_pud",
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
      "addr": 18446744071595746875,
      "name": "set_pud",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235753,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619286254,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204048,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562714,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596973433,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677847,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690706,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730229,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834603,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582981457,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061677,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076836,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304973,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363291,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596267782,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596271157,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525833,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578750,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233392,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590250,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597901865,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711975,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725234,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765173,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009051,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583135007,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243221,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259092,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583542845,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599771,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597150470,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155893,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490349888,
      "name": "set_pud",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:530",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:pud_free_pmd_page",
        "arch/arm64/mm/mmu.c:pud_clear_huge",
        "arch/arm64/mm/mmu.c:pud_set_huge",
        "arch/arm64/mm/mmu.c:alloc_init_pud",
        "arch/arm64/mm/mmu.c:early_fixmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490463160,
      "name": "set_pud",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:530",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:__unmap_hyp_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492751472,
      "name": "set_pud",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:530",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492810076,
      "name": "set_pud",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:530",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492988828,
      "name": "set_pud",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:530",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503922476,
      "name": "set_pud",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:530",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271359458,
      "name": "set_pud",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:46",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272734106,
      "name": "set_pud",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:46",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272772644,
      "name": "set_pud",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:46",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272890634,
      "name": "set_pud",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:46",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270897316,
      "name": "set_pud",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:46",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590217,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620755,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076756,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298010,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589767408,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071579374332,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398031,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425217,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314664,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379906,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520415,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781953,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926514,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935187,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668041,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698570,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076340,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579299210,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590210816,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071579374252,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397951,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425137,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305864,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371106,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511727,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225361,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259922,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266963,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
  "name": "set_pud",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668046,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698576,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080436,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579308042,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590261184,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
      "addr": 18446744071579382732,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406447,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434321,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369864,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434994,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576783,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275719,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395442,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402131,
      "name": "set_pud",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:489",
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
void set_pud(pud_t * pudp, pud_t pud)
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
void set_pud(pud_t * pudp, pud_t pud)
```
</details>
</li>
</ul>

# Function: <code>set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977278,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995801,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060503,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579221011,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347115,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595065309,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288507,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308590,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:pmd_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316312,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/kmmio.c",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595140101,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992540,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056841,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579221256,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848645,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595231029,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294553,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308510,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321885,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580869,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:456",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595382783,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994380,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055853,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233410,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063458,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595474086,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310053,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323742,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337117,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586765562,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578966110,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596304048,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048085,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579231006,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290138,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395638,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307981,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321100,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331086,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888872,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578969305,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602621817,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056937,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246611,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855447,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602714706,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330325,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344284,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356607,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602724794,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377768,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972213,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602790624,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061845,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579259091,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589234607,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602887383,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340965,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355674,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368823,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602896269,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681568,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:441",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970327,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066421,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282755,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478237,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:__set_pte_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684393,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367868,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382858,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396279,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604693578,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820789,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578977334,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074965,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579297023,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359378,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__set_pte_vaddr",
        "arch/x86/mm/init_64.c:set_pte_init",
        "arch/x86/mm/init_64.c:set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604783929,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382711,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398320,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411655,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604793588,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123893,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:447",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578979734,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076965,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302575,
      "name": "set_pte",
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
      "addr": 18446744071579363618,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__set_pte_vaddr",
        "arch/x86/mm/init_64.c:set_pte_init",
        "arch/x86/mm/init_64.c:set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809684,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387015,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401632,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414839,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604819311,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328693,
      "name": "set_pte",
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
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990082,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
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
      "addr": 18446744071579087178,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332556,
      "name": "set_pte",
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
      "addr": 18446744071579391153,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_init"
      ]
    },
    {
      "addr": 18446744071609148353,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411007,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427364,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:unmap_pte_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444729,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157503,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:449",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150829,
      "name": "set_pte",
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
      "addr": 18446744071578987792,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393616,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982018,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991570,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
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
      "addr": 18446744071579000960,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080507,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089242,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095394,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251429,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261104,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334140,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367056,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395431,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:set_pte_init"
      ]
    },
    {
      "addr": 18446744071591270092,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ]
    },
    {
      "addr": 18446744071579411649,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427060,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
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
      "addr": 18446744071579442219,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227986,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274669,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438727,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541660,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582694,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:copy_pte_range"
      ]
    },
    {
      "addr": 18446744071581637502,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644109,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667273,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674189,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696321,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740658,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759378,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816421,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692390,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857230,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925869,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946432,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973871,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582072804,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643340,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809925,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461221,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236813,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
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
      "addr": 18446744071578989280,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266306,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591270092,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581558944,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991106,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000309,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071579008960,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087368,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095800,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579101599,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591195188,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262848,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336829,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371408,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398919,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:set_pte_init"
      ]
    },
    {
      "addr": 18446744071591212639,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ]
    },
    {
      "addr": 18446744071579414817,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430071,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071579444510,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence",
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368749,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291303,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459187,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564876,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604401,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy"
      ]
    },
    {
      "addr": 18446744071581659145,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665616,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581689237,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695414,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768943,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786378,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844416,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635140,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892362,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948103,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972360,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582002360,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582097827,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671350,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838645,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344977,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179479,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071578998240,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208617,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591212639,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581581888,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579008162,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018003,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071579110468,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119161,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579125519,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060973,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304096,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392151,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432624,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461159,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:set_pte_init"
      ]
    },
    {
      "addr": 18446744071592086935,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ]
    },
    {
      "addr": 18446744071579477697,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494250,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071579509518,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence",
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615300293,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535593,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829644,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870593,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071581927426,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934304,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961174,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967592,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051599,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070154,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135697,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172580,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071582187035,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582236217,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_unprotect",
        "mm/kfence/core.c:kfence_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252693,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274813,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582304120,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582412432,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997606,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171669,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865297,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035559,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
      "addr": 18446744071579015920,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082255,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592086935,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581846848,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071582170352,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025697,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037189,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
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
      "addr": 18446744071579141531,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151730,
      "name": "set_pte",
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
      "addr": 18446744071579159817,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827481,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359700,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458618,
      "name": "set_pte",
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
      "addr": 18446744071579501616,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537159,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:set_pte_init"
      ]
    },
    {
      "addr": 18446744071593853726,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ]
    },
    {
      "addr": 18446744071579556145,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574605,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
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
      "addr": 18446744071579592877,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence",
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617080362,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884520,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222893,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266147,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582335078,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582343301,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582380472,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582390386,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476802,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509254,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584950,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631470,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
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
      "addr": 18446744071582646759,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706304,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718644,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741550,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758155,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925677,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672389,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588151370,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800982,
      "name": "set_pte",
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
      "addr": 18446744071579034560,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579532432,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593853726,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582239152,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071582628336,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054172,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066728,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185915,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200585,
      "name": "set_pte",
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
      "addr": 18446744071579210003,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271054,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430740,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547760,
      "name": "set_pte",
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
      "addr": 18446744071579598800,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596431301,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627718748,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663070,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683287,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
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
      "addr": 18446744071579704054,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence",
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627734541,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317774,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582712489,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757634,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582835948,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844616,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582883952,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896656,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991094,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028298,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114706,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ]
    },
    {
      "addr": 18446744071583122292,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
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
      "addr": 18446744071596455171,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166670,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231921,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245659,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273993,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291671,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481373,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584279909,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589545195,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:439",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746746,
      "name": "set_pte",
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
      "addr": 18446744071582729984,
      "name": "set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583060112,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054076,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066600,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189980,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204644,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215553,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277334,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442756,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563057,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611520,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596972085,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619476220,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677220,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697143,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
      "addr": 18446744071579717542,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence",
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619493812,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518887,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926875,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973406,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583050826,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058850,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098803,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108266,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
      "addr": 18446744071583202059,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237932,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325093,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332557,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
      "addr": 18446744071596996501,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382867,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451113,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465309,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496152,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510657,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697245,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_pte_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510069,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589846794,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596271028,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
      "addr": 18446744071582946176,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078979,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579091688,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219216,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233988,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245071,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306947,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579472899,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579590593,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579643219,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597900533,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621772828,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711348,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731671,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
      "addr": 18446744071579752262,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence",
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621790772,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685299,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583096739,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583163727,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:handle_pte_marker"
      ]
    },
    {
      "addr": 18446744071583232608,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240573,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583267123,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583294134,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437595,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468915,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583561698,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566590,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600707,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583618707,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583643921,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583659795,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583681443,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583700968,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891011,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584729955,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590183235,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597155764,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
      "addr": 18446744071583121504,
      "name": "set_pte",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510824652,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "arch/arm64/kernel/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/efi.c:set_permissions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490347408,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:init_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490352960,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "arch/arm64/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/pageattr.c:change_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490358696,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush",
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect",
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags",
        "arch/arm64/mm/hugetlbpage.c:huge_pte_clear",
        "arch/arm64/mm/hugetlbpage.c:set_huge_swap_pte_at",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492406344,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492593740,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492719576,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753112,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798708,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492802480,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492818636,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492827524,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492903852,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492933444,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503922172,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493034968,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117364,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129540,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493164052,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493272256,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493856736,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498279040,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503826328,
      "name": "set_pte",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:211",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270613914,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "arch/riscv/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:paging_init",
        "arch/riscv/mm/init.c:paging_init",
        "arch/riscv/mm/init.c:get_pmd_virt",
        "arch/riscv/mm/init.c:get_pmd_virt",
        "arch/riscv/mm/init.c:get_pte_virt",
        "arch/riscv/mm/init.c:get_pte_virt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272622584,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714022,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272734598,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765496,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272768086,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272777114,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272783558,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272828190,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272852102,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272895712,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270897116,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272910784,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272949734,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024400,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273427914,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279720354,
      "name": "set_pte",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:326",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578980086,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077317,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298383,
      "name": "set_pte",
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
      "addr": 18446744071579359522,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__set_pte_vaddr",
        "arch/x86/mm/init_64.c:set_pte_init",
        "arch/x86/mm/init_64.c:set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723626,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382919,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397536,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410679,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604733191,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935477,
      "name": "set_pte",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578979670,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076901,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579299583,
      "name": "set_pte",
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
      "addr": 18446744071579359442,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__set_pte_vaddr",
        "arch/x86/mm/init_64.c:set_pte_init",
        "arch/x86/mm/init_64.c:set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604801193,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382839,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397456,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410599,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604810758,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267253,
      "name": "set_pte",
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
  "name": "set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578980262,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080997,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579308415,
      "name": "set_pte",
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
      "addr": 18446744071579367874,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__set_pte_vaddr",
        "arch/x86/mm/init_64.c:set_pte_init",
        "arch/x86/mm/init_64.c:set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813812,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391625,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405952,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419463,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604823468,
      "name": "set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402421,
      "name": "set_pte",
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
void set_pte(pte_t * ptep, pte_t pte)
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

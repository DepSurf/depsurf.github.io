# Function: <code>pud_large</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977809,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:609",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348227,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:609",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280031,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:609",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289854,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:609",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pgd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308889,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:609",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310336,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:609",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
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
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595141876,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277063,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279085,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298900,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308617,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311112,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320495,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580528,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
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
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384546,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292391,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294349,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314372,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323849,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326328,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335719,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765200,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:646",
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
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305820,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289899,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293629,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311745,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321209,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329805,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888496,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:785",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578998386,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579309260,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579312607,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334338,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344393,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354896,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602722021,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377369,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:793",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998386,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579304512,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579001795,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579320651,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579324982,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345169,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355765,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366429,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382735,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897335,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681223,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:835",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001795,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579316880,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579000691,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579344955,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579349046,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371761,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382949,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394054,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410304,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694719,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820448,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071579000691,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579341616,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579008115,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579360603,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579363753,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386865,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398421,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408989,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426095,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794741,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123552,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
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
      "addr": 18446744071579008115,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579356992,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010472,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579364843,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579367993,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390257,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401733,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412173,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429263,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820464,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328352,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
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
      "addr": 18446744071579010472,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579361232,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609041778,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391765,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397166,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411109,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430631,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454687,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609158864,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608750,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582043404,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150603,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:881",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612105136,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396037,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403534,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411749,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421873,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451551,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612229462,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190900,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656204,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582092364,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236587,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614244892,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399448,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406733,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414917,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424931,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454016,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614370216,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220361,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611065,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677650,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581699066,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117436,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179253,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615164968,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461748,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469288,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477797,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488558,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519410,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615302192,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460347,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878035,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946851,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581970863,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433820,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035333,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616930967,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537824,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546179,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556261,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568570,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603533,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617082457,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807595,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582277648,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582356128,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582394035,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950623,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800753,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:849",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627536907,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596432338,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645413,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663237,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676808,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716543,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627737406,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234210,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514898,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770144,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858096,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582900297,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507952,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746514,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:867",
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
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619282891,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596973122,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659829,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677397,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690680,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730127,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619496708,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437440,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716862,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986304,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073600,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583115433,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722832,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270802,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621575323,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597901554,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693813,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711525,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725208,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765071,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621793540,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605952,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886206,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161648,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255648,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583298329,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923536,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155538,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1090",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010824,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579360747,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579363897,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386161,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397637,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408013,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425103,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734344,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935136,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
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
      "addr": 18446744071579010824,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579357136,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579291889,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295212,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307875,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327077,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337767,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354160,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701965,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648410,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010408,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579360667,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579363817,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386081,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397557,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407933,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425023,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811911,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266912,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
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
      "addr": 18446744071579010408,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579357056,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int pud_large(pud_t pud)
```

```json
{
  "name": "pud_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579013624,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579369099,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579372249,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394593,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406053,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416797,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434207,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824621,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402080,
      "name": "pud_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:877",
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
      "addr": 18446744071579013624,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579365488,
      "name": "pud_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int pud_large(pud_t pud)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pud_large(pud_t pud)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pud_large(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pud_large(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pud_large(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pud_large(pud_t pud)
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
int pud_large(pud_t pud)
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

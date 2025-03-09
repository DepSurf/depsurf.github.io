# Function: <code>pmd_large</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977931,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:162",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347650,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:162",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:162",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579289232,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:162",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308969,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:162",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310543,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:162",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595141969,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851425,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579288762,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308696,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311188,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320592,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580612,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384639,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066188,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579304282,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323928,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326404,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335816,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765284,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305940,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588293040,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302024,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321288,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329958,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888643,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
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
int pmd_large(pmd_t pte)
```

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578998416,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579309363,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579313846,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323566,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344479,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355253,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602722843,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377537,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:221",
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
      "addr": 18446744071578998416,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071579305280,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602792508,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237276,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325129,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
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
      "addr": 18446744071579334484,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355855,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366772,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895127,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897763,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681401,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604586373,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481314,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349193,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
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
      "addr": 18446744071579361028,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383039,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394406,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411256,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695147,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820622,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:233",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604681765,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941045,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363894,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
      "addr": 18446744071579375625,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398511,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409311,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426945,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604795173,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123726,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604694207,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168597,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368134,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
      "addr": 18446744071579379913,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401823,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412495,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430186,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820905,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328526,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
int pmd_large(pmd_t pte)
```

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579018498,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd"
      ]
    },
    {
      "addr": 18446744071579391870,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579402025,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411199,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420815,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454016,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    },
    {
      "addr": 18446744071579456127,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    },
    {
      "addr": 18446744071581608079,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582043243,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150718,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
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
      "addr": 18446744071579018498,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579393834,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579454016,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579456127,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int pmd_large(pmd_t pte)
```

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591242846,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd"
      ]
    },
    {
      "addr": 18446744071579396142,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579411839,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419281,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450880,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    },
    {
      "addr": 18446744071591273198,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    },
    {
      "addr": 18446744071581191043,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655503,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582092203,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236702,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
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
      "addr": 18446744071591242846,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071591266462,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579450880,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071591273198,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int pmd_large(pmd_t pte)
```

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591185956,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579399553,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579414997,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424049,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453376,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    },
    {
      "addr": 18446744071591216146,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    },
    {
      "addr": 18446744071581220503,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610409,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676990,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581699233,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117275,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179368,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
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
      "addr": 18446744071591185956,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591208773,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579453376,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071591216146,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int pmd_large(pmd_t pte)
```

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592048128,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071592082411,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579477877,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487663,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518688,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    },
    {
      "addr": 18446744071592092968,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    },
    {
      "addr": 18446744071581460488,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877379,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946218,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581971029,
      "name": "pmd_large",
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
      "addr": 18446744071582171247,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433659,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035448,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
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
      "addr": 18446744071592048128,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592082411,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579518688,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071592092968,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int pmd_large(pmd_t pte)
```

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593814690,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579532864,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579556373,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567589,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602768,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ]
    },
    {
      "addr": 18446744071593860447,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    },
    {
      "addr": 18446744071581807734,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582277247,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355341,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582394199,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629909,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_range",
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950415,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800866,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
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
      "addr": 18446744071593814690,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579532864,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579602768,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071593860447,
      "name": "pmd_large",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627537056,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438921,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_check_pmd",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579663381,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675805,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716869,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627738238,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234356,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582769715,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857465,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582900462,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121692,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177688,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583507728,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746632,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:228",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619283034,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596979737,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_check_pmd",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579677525,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689677,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730437,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619497358,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437531,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985852,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072999,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583115592,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331964,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722608,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270914,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:229",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621575466,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597908169,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_check_pmd",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579711653,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724205,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765381,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621794190,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606043,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161196,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255047,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583298488,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583567333,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_pmd_entry",
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923312,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155650,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:265",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604620488,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770885,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364038,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
      "addr": 18446744071579375817,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397727,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408335,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426026,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734785,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935310,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589493723,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295299,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
      "addr": 18446744071579305383,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327151,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338051,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355146,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702406,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648489,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698303,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214293,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363958,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
      "addr": 18446744071579375737,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397647,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408255,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425946,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812352,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267086,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
  "name": "pmd_large",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698309,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590264661,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372390,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
      "addr": 18446744071579384217,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406143,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417119,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435130,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604825062,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402254,
      "name": "pmd_large",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int pmd_large(pmd_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int pmd_large(pmd_t pte)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pmd_large(pmd_t pte)
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
int pmd_large(pmd_t pte)
```
</details>
</li>
</ul>

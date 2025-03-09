# Function: <code>pud_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977789,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:155",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278014,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:155",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281094,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:155",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292617,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:155",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595140593,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277378,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280433,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294800,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595383275,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292706,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295697,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310300,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:166",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579290071,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292948,
      "name": "pud_pfn",
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
      "addr": 18446744071579306270,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580881280,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151690,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310145,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:198",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579313408,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:198",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328775,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:198",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602724521,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:198",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966068,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:198",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272746,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:198",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305344,
      "name": "pud_pfn",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321589,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579339758,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895975,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102359,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421610,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:206",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316640,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345893,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:208",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579366738,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:208",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693284,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:208",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180794,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:208",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507512,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:208",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341376,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361576,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579381750,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793301,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250540,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617137,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749048,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356752,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365816,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579386054,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604819022,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309148,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687985,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821160,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360992,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579392816,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579424939,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157215,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510109,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905336,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582038535,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394972,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397111,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579424635,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227709,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550237,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957703,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087415,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591268374,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579400361,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579427649,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368486,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573357,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699599,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983633,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112492,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:226",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591210957,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579462674,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579491818,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615300036,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837968,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971396,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582285617,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428812,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:197",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592084841,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539149,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579572022,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605032,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230024,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394544,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762679,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943545,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:200",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533824,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642577,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680373,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718843,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582720224,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900815,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296599,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500424,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579656625,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694261,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579732429,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936704,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115946,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515688,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583716844,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:202",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579690497,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728789,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767373,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111936,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298842,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583709655,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917484,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:238",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pud_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1325",
      "file": "mm/gup.c",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361720,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579381958,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732902,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277996,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656721,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789896,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356896,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292696,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311419,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700575,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224241,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596788,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727582,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361640,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579381878,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810469,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269196,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648033,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781208,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356816,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pud_pfn(pud_t pud)
```

```json
{
  "name": "pud_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579370072,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579391037,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604823179,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333094,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714465,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850216,
      "name": "pud_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365248,
      "name": "pud_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pud_pfn(pud_t pud)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int pud_pfn(pud_t pud)
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
long unsigned int pud_pfn(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int pud_pfn(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int pud_pfn(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int pud_pfn(pud_t pud)
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
long unsigned int pud_pfn(pud_t pud)
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

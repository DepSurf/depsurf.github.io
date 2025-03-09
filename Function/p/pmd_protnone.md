# Function: <code>pmd_protnone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:508",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580657883,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:508",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675422,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901923,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579311318,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766120,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790087,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031625,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579326534,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831927,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854543,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106915,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:544",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880256,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:683",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899440,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:683",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156603,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:683",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965117,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:693",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001898,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:693",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279170,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:693",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394389,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:693",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581101481,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:735",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139039,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:735",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427656,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:735",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544978,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:735",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581179438,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:760",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211977,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:760",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513228,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:760",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628261,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:760",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249649,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288115,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622985,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747348,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308257,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346835,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693849,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819560,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
int pmd_protnone(pmd_t pmd)
```

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581496864,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581551601,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911374,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036265,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496864,
      "name": "pmd_protnone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pmd_protnone(pmd_t pmd)
```

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581537376,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581594737,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956575,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085097,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537376,
      "name": "pmd_protnone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pmd_protnone(pmd_t pmd)
```

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581575379,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615405,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982655,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111355,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:812",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559216,
      "name": "pmd_protnone",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_protnone(pmd_t pmd)
```

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581840009,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:783",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882214,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:783",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284639,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:783",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427675,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:783",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823536,
      "name": "pmd_protnone",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_protnone(pmd_t pmd)
```

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582232133,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:781",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284066,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:781",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582768031,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:781",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944220,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:781",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215088,
      "name": "pmd_protnone",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582713092,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582776496,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583302475,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:can_change_pmd_writable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583501158,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582938851,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:799",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992759,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:799",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583521803,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:799",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:can_change_pmd_writable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715589,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:799",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583114081,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1014",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174571,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1014",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583716691,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1014",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:can_change_pmd_writable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913609,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1014",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:345",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:345",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493138572,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493282624,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:345",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1031",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1031",
      "file": "mm/memory.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286058400,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1107",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286111968,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1107",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286622652,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1107",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286818892,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1107",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1031",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_protnone",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:1031",
      "file": "mm/memory.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581277105,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315683,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662585,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788296,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581223229,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259153,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602310,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581726121,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581268305,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306883,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653897,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779608,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "pmd_protnone",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581332187,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370883,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720306,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848568,
      "name": "pmd_protnone",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:777",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
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
int pmd_protnone(pmd_t pmd)
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
int pmd_protnone(pmd_t pmd)
```
</details>
</li>
</ul>

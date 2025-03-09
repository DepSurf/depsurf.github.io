# Function: <code>xen_mc_issue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962137,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968464,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_write_cr3_init",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968464,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960368,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970378,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_write_cr3_init",
        "arch/x86/xen/mmu.c:xen_set_pgd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965360,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962112,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972154,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_write_cr3_init",
        "arch/x86/xen/mmu.c:xen_set_pgd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967184,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578953521,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973873,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983303,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:42",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976048,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955777,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578977361,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986110,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979232,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957884,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980511,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996398,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982032,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978191,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985756,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980096,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578985167,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989772,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986960,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987535,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992524,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989328,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578997802,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579003193,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002576,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999579,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005256,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579004032,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579007008,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579010272,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007008,
      "name": "xen_mc_issue.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579010272,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024896,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579028464,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024896,
      "name": "xen_mc_issue.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071579028464,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579043488,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579048448,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043488,
      "name": "xen_mc_issue.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071579048448,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579073712,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579079280,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073712,
      "name": "xen_mc_issue.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071579079280,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579073552,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579079088,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073552,
      "name": "xen_mc_issue.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071579079088,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098976,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579104864,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098976,
      "name": "xen_mc_issue.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071579104864,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987887,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992876,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989680,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987471,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992460,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989264,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_issue(unsigned int mode)
```

```json
{
  "name": "xen_mc_issue",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578988447,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993731,
      "name": "xen_mc_issue",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990432,
      "name": "xen_mc_issue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void xen_mc_issue(unsigned int mode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_mc_issue(unsigned int mode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_mc_issue(unsigned int mode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_mc_issue(unsigned int mode)
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
void xen_mc_issue(unsigned int mode)
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

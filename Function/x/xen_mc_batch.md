# Function: <code>xen_mc_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962054,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578968336,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578968336,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960299,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578970071,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578965248,
      "name": "xen_mc_batch",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578962043,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578971847,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578967072,
      "name": "xen_mc_batch",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578953424,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973805,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578983062,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:22",
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
      "addr": 18446744071578975936,
      "name": "xen_mc_batch",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955680,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578977293,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578985862,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578979104,
      "name": "xen_mc_batch",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957790,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980443,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578996085,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
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
      "addr": 18446744071578981904,
      "name": "xen_mc_batch",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578978123,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578985662,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578979968,
      "name": "xen_mc_batch",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578985099,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578989678,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578986832,
      "name": "xen_mc_batch",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987467,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578992430,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578989200,
      "name": "xen_mc_batch",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578996960,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579002704,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578996960,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071579002704,
      "name": "xen_mc_batch",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999511,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071579005162,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071579004464,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579007728,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579010384,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
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
      "addr": 18446744071579007728,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071579010384,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579025776,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579028576,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
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
      "addr": 18446744071579025776,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071579028576,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041376,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579048576,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579041376,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579048576,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070832,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579079440,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579070832,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071579079440,
      "name": "xen_mc_batch",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070656,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579079248,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579070656,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071579079248,
      "name": "xen_mc_batch",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579095872,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt"
      ]
    },
    {
      "addr": 18446744071579105024,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071579095872,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071579105024,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987819,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578992782,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578989552,
      "name": "xen_mc_batch",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578987403,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578992366,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578989136,
      "name": "xen_mc_batch",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void xen_mc_batch()
```

```json
{
  "name": "xen_mc_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578988379,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578993637,
      "name": "xen_mc_batch",
      "external": false,
      "loc": "arch/x86/xen/multicalls.h:23",
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
      "addr": 18446744071578990288,
      "name": "xen_mc_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void xen_mc_batch()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_mc_batch()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_mc_batch()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_mc_batch()
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
void xen_mc_batch()
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

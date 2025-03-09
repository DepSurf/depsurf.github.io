# Function: <code>paravirt_get_lazy_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258265,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:305",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258464,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579257669,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:288",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257872,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579271189,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:288",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_write_cr3",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:__xen_pgd_pin",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pgd",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271392,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579267909,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:288",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268096,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284873,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:298",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285072,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296345,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:304",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296544,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320873,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:285",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321072,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336053,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:273",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336256,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579340261,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:273",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579340464,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579369685,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:255",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369888,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579368693,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:255",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368896,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579372981,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:223",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373184,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579434277,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:223",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434480,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579503472,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:247",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503856,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579601104,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:230",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601536,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579613856,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:226",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614288,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336165,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:273",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336368,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579269369,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:273",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269392,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336085,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:273",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336288,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```

```json
{
  "name": "paravirt_get_lazy_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579344480,
      "name": "paravirt_get_lazy_mode",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:273",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344736,
      "name": "paravirt_get_lazy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
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
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
enum paravirt_lazy_mode paravirt_get_lazy_mode()
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

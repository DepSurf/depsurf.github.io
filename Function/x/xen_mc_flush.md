# Function: <code>xen_mc_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966048,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:55",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_end_context_switch",
        "arch/x86/xen/enlighten.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/mmu.c:xen_cleanhighmap",
        "arch/x86/xen/mmu.c:xen_leave_lazy_mmu",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966048,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962896,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:55",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/enlighten.c:xen_end_context_switch",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu.c:xen_cleanhighmap",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962896,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964720,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:55",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten.c:xen_load_tls",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/enlighten.c:xen_end_context_switch",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu.c:xen_cleanhighmap",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964720,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578951248,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:55",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951248,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953440,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953440,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578956000,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956000,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002640,
      "name": "xen_mc_flush.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579001184,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010086,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579008624,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012390,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579010944,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020422,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579018976,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242889,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579021312,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186390,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579024304,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049240,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579042592,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593815558,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071579064496,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096400,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096400,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096048,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096048,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121840,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121840,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012742,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579011296,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012326,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579010880,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void xen_mc_flush()
```

```json
{
  "name": "xen_mc_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_mc_flush",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:56",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_tls",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu",
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
        "arch/x86/xen/mmu_pv.c:xen_cleanhighmap",
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:__xen_mc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015895,
      "name": "xen_mc_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579014160,
      "name": "xen_mc_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
void xen_mc_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_mc_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_mc_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_mc_flush()
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
void xen_mc_flush()
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

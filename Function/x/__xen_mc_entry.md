# Function: <code>__xen_mc_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966480,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:132",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966480,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578963328,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:132",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_clts",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963328,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578965152,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:132",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_write_cr0",
        "arch/x86/xen/enlighten.c:xen_load_sp0",
        "arch/x86/xen/enlighten.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten.c:xen_set_ldt",
        "arch/x86/xen/mmu.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu.c:xen_flush_tlb",
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965152,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578951664,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:132",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_single",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951664,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578953872,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:133",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953872,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578956432,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:133",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_all",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956432,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001680,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001680,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009104,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009104,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579011408,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011408,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579019440,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019440,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021744,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021744,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024752,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024752,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579043104,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043104,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065072,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065072,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579097232,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097232,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096896,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096896,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579122688,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122688,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579011760,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011760,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579011344,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011344,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```

```json
{
  "name": "__xen_mc_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579014688,
      "name": "__xen_mc_entry",
      "external": true,
      "loc": "arch/x86/xen/multicalls.c:138",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579014688,
      "name": "__xen_mc_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
struct multicall_space __xen_mc_entry(size_t args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct multicall_space __xen_mc_entry(size_t args)
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
struct multicall_space __xen_mc_entry(size_t args)
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

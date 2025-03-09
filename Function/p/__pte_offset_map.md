# Function: <code>__pte_offset_map</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
pte_t * __pte_offset_map(pmd_t * pmd, long unsigned int addr, pmd_t * pmdvalp)
```

```json
{
  "name": "__pte_offset_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583078256,
      "name": "__pte_offset_map",
      "external": true,
      "loc": "mm/pgtable-generic.c:235",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "kernel/events/core.c:perf_get_pgtable_size",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/pagewalk.c:walk_pte_range",
        "mm/pgtable-generic.c:__pte_offset_map_lock",
        "mm/pgtable-generic.c:pte_offset_map_nolock",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583078256,
      "name": "__pte_offset_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
pte_t * __pte_offset_map(pmd_t * pmd, long unsigned int addr, pmd_t * pmdvalp)
```

```json
{
  "name": "__pte_offset_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260576,
      "name": "__pte_offset_map",
      "external": true,
      "loc": "mm/pgtable-generic.c:280",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:map_tboot_page",
        "kernel/events/core.c:perf_get_pgtable_size",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/memory.c:alloc_anon_folio",
        "mm/pagewalk.c:walk_pte_range",
        "mm/pgtable-generic.c:__pte_offset_map_lock",
        "mm/pgtable-generic.c:pte_offset_map_nolock",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260576,
      "name": "__pte_offset_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
pte_t * __pte_offset_map(pmd_t * pmd, long unsigned int addr, pmd_t * pmdvalp)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

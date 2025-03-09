# Function: <code>lruvec_stat_mod_folio</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lruvec_stat_mod_folio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581986966,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:642",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned"
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
  "name": "lruvec_stat_mod_folio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582422814,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:636",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned"
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
  "name": "lruvec_stat_mod_folio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582628027,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:642",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void lruvec_stat_mod_folio(struct folio * folio, enum node_stat_item idx, int val)
```

```json
{
  "name": "lruvec_stat_mod_folio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579707456,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pud_free_tlb",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ]
    },
    {
      "addr": 18446744071579867776,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack"
      ]
    },
    {
      "addr": 18446744071582788832,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned"
      ]
    },
    {
      "addr": 18446744071583123152,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc"
      ]
    },
    {
      "addr": 18446744071583258544,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:pte_free_now"
      ]
    },
    {
      "addr": 18446744071583386656,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:free_large_kmalloc",
        "mm/slub.c:__kmalloc_large_node"
      ]
    },
    {
      "addr": 18446744071583696480,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 0,
      "name": "lruvec_stat_mod_folio",
      "external": false,
      "loc": "include/linux/vmstat.h:562",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707456,
      "name": "lruvec_stat_mod_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071579867776,
      "name": "lruvec_stat_mod_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582788832,
      "name": "lruvec_stat_mod_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583123152,
      "name": "lruvec_stat_mod_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583258544,
      "name": "lruvec_stat_mod_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583386656,
      "name": "lruvec_stat_mod_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583696480,
      "name": "lruvec_stat_mod_folio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void lruvec_stat_mod_folio(struct folio * folio, enum node_stat_item idx, int val)
```
</details>
</li>
</ul>

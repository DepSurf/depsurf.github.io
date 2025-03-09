# Function: <code>__mod_lruvec_page_state</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580711340,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:597",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958234,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:597",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796908,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:600",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059978,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:600",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580935996,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:649",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095497,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:649",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198606,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:649",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356683,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:649",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581003823,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:689",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174365,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:689",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281954,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:689",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441981,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:689",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068208,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:683",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356560,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:683",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581124176,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416120,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581273157,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:697",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310816,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:697",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389875,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:697",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618206,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:697",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901934,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:697",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933520,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:697",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015872,
      "name": "__mod_lruvec_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:850",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:___pmd_free_tlb",
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "kernel/fork.c:account_kernel_stack",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015872,
      "name": "__mod_lruvec_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041632,
      "name": "__mod_lruvec_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:738",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041632,
      "name": "__mod_lruvec_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348256,
      "name": "__mod_lruvec_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:760",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:build_detached_freelist",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348256,
      "name": "__mod_lruvec_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843760,
      "name": "__mod_lruvec_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:756",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:mod_lruvec_page_state",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843760,
      "name": "__mod_lruvec_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389472,
      "name": "__mod_lruvec_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:826",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:mod_lruvec_page_state",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389472,
      "name": "__mod_lruvec_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610176,
      "name": "__mod_lruvec_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:851",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:mod_lruvec_page_state",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610176,
      "name": "__mod_lruvec_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492498784,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492816136,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226365848,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 3226624528,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285782632,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286197704,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272556470,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272775642,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581093024,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384968,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581040194,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327736,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581084224,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376168,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_lruvec_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581146144,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440024,
      "name": "__mod_lruvec_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:720",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```
</details>
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
void __mod_lruvec_page_state(struct page * page, enum node_stat_item idx, int val)
```
</details>
</li>
</ul>

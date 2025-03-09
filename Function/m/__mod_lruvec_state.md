# Function: <code>__mod_lruvec_state</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580936057,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:613",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095558,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:613",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198669,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:613",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356744,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:613",
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
  "name": "__mod_lruvec_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581003884,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:653",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174442,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:653",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282017,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:653",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442042,
      "name": "__mod_lruvec_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:653",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673152,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673152,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745408,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745408,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966864,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:726",
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
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966864,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015792,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:839",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/mlock.c:__munlock_pagevec",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015792,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041552,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:727",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041552,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348192,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:749",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348192,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843680,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:745",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__folio_activate",
        "mm/swap.c:__folio_activate",
        "mm/swap.c:pagevec_move_tail_fn",
        "mm/swap.c:pagevec_move_tail_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:mod_lruvec_state",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843680,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389376,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:815",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:lru_gen_add_folio",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:reset_batch_size",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:lru_gen_add_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:mod_lruvec_state",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389376,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610080,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:840",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:lru_gen_add_folio",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:reset_batch_size",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:lru_gen_add_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:mod_lruvec_state",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610080,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583804896,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:888",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:lru_gen_add_folio",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:reset_batch_size",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:lru_gen_add_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:mod_lruvec_state",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__lruvec_stat_mod_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804896,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493198368,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493198368,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226829848,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226829848,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286701984,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286701984,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272977720,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272977720,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714144,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714144,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653056,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653056,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705456,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705456,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772800,
      "name": "__mod_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:735",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772800,
      "name": "__mod_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __mod_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

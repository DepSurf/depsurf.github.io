# Function: <code>xas_store</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589430592,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:751",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_entry",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_reserve",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430592,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1340
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589888352,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:768",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_entry",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589888352,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1583
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590114304,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590114304,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1583
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118432,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118432,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585268848,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:772",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268848,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1103
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151632,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:772",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151632,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1544
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604080,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:772",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604080,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1824
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586761040,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:777",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586761040,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1922
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595925536,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:777",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595925536,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1741
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596443840,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:775",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596443840,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1839
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597339200,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:775",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_writeback_one",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_folio",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_delete_node",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597339200,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1839
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503895648,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503895648,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236524948,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236524948,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1508
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297764560,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_entry",
        "fs/dax.c:dax_unlock_entry",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297764560,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1916
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279784548,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279784548,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1154
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589716560,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716560,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1583
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589442336,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589442336,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1583
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590159936,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590159936,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1583
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
void * xas_store(struct xa_state * xas, void * entry)
```

```json
{
  "name": "xas_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590210576,
      "name": "xas_store",
      "external": true,
      "loc": "lib/xarray.c:769",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_replace_entry",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:__xa_alloc",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:__xa_store",
        "lib/xarray.c:__xa_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590210576,
      "name": "xas_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1583
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * xas_store(struct xa_state * xas, void * entry)
```
</details>
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

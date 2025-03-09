# Function: <code>xas_load</code>

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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425520,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:225",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_reserve",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425520,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589883392,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:230",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883392,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109296,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109296,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585114288,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114288,
      "name": "xas_load",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263792,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263792,
      "name": "xas_load",
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585146624,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:pagecache_get_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146624,
      "name": "xas_load",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:pagecache_get_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/idr.c:ida_free",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345243,
      "name": "xas_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585598016,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586760879,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:233",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_load"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:__filemap_get_folio",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752464,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595925359,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:233",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_load"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:__filemap_get_folio",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595916544,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596443663,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:235",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_load"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_entry",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_page",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596434592,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597339023,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:235",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_load"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_entry",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:dax_lock_folio",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:xa_get_order",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597329952,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503890640,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503890640,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236519272,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:clear_shadow_entry",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236519272,
      "name": "xas_load",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297757168,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297757168,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279782174,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279782174,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711552,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711552,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437328,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437328,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590154928,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154928,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xas_load(struct xa_state * xas)
```

```json
{
  "name": "xas_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590205312,
      "name": "xas_load",
      "external": true,
      "loc": "lib/xarray.c:231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/shmem.c:shmem_replace_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_lock_page",
        "lib/idr.c:ida_free",
        "lib/xarray.c:__xa_clear_mark",
        "lib/xarray.c:__xa_set_mark",
        "lib/xarray.c:__xa_insert",
        "lib/xarray.c:__xa_cmpxchg",
        "lib/xarray.c:xa_load",
        "lib/xarray.c:xas_find",
        "lib/xarray.c:__xas_next",
        "lib/xarray.c:__xas_prev",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205312,
      "name": "xas_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xas_load(struct xa_state * xas)
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

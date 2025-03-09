# Function: <code>xas_find</code>

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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589426192,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1055",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426192,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589884064,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1074",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589884064,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590110000,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590110000,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585114976,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "fs/fuse/file.c:__readahead_batch",
        "fs/fuse/file.c:__readahead_batch",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114976,
      "name": "xas_find",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585264480,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1231",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/fuse/file.c:__readahead_batch",
        "fs/fuse/file.c:__readahead_batch",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585264480,
      "name": "xas_find",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585147312,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1232",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_needs_writeback",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/fuse/file.c:__readahead_batch",
        "fs/fuse/file.c:__readahead_batch",
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_gap_alignment",
        "lib/iov_iter.c:iov_iter_gap_alignment",
        "lib/iov_iter.c:iov_iter_alignment",
        "lib/iov_iter.c:iov_iter_alignment",
        "lib/iov_iter.c:iov_iter_advance",
        "lib/iov_iter.c:iov_iter_advance",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585147312,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585599024,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1232",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_needs_writeback",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_readahead",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599024,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586752560,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1239",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_readahead",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752560,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595916656,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1239",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/squashfs/file.c:__readahead_batch",
        "fs/squashfs/file.c:__readahead_batch",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_readahead",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595916656,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596434704,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1237",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/madvise.c:shmem_swapin_range",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/squashfs/file.c:__readahead_batch",
        "fs/squashfs/file.c:__readahead_batch",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_readahead",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596434704,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597330064,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1237",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:next_uptodate_folio",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_writeback",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/list_lru.c:memcg_destroy_list_lru",
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:shmem_swapin_range",
        "mm/swap_state.c:clear_shadow_from_swap_cache",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:offset_iterate_dir",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/dax.c:dax_layout_busy_page_range",
        "fs/squashfs/file.c:__readahead_batch",
        "fs/squashfs/file.c:__readahead_batch",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_readahead",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/core/datagram.c:csum_and_copy_to_iter",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597330064,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503891408,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503891408,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236520140,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236520140,
      "name": "xas_find",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297758080,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297758080,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279782742,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279782742,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589712256,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712256,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589438032,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589438032,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155632,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155632,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void * xas_find(struct xa_state * xas, long unsigned int max)
```

```json
{
  "name": "xas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590206080,
      "name": "xas_find",
      "external": true,
      "loc": "lib/xarray.c:1081",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:filemap_range_has_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "lib/idr.c:ida_destroy",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_extract",
        "lib/xarray.c:xa_find_after",
        "lib/xarray.c:xa_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590206080,
      "name": "xas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
void * xas_find(struct xa_state * xas, long unsigned int max)
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

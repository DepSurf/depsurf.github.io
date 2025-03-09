# Function: <code>folio_test_hugetlb</code>

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
  "name": "folio_test_hugetlb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581883933,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942955,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:read_cache_page_gfp",
        "mm/filemap.c:read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:filemap_free_folio",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581993545,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/folio-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113615,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:folio_mapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582219040,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:check_and_migrate_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366417,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582616284,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582717572,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933852,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506578,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:read_file_data_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583610278,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586081732,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:830",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
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
  "name": "folio_test_hugetlb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317183,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582377382,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:read_cache_page_gfp",
        "mm/filemap.c:read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_free_folio",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429972,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/folio-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582447221,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542205,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570740,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705952,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:collect_longterm_unpinnable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760158,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869393,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012584,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027533,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116421,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140226,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246836,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583341297,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380414,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487225,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489607,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104664,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216571,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063078,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:827",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool folio_test_hugetlb(struct folio * folio)
```

```json
{
  "name": "folio_test_hugetlb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583327382,
      "name": "folio_test_hugetlb",
      "external": true,
      "loc": "mm/hugetlb.c:2086",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:get_hwpoison_hugetlb_folio",
        "mm/hugetlb.c:isolate_hugetlb",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:read_cache_page_gfp",
        "mm/filemap.c:read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_free_folio",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/filemap.c:__filemap_remove_folio",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/folio-compat.c:pagecache_get_page",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:__folio_put",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/gup.c:folio_fast_pin_allowed",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:unuse_pte",
        "mm/mempolicy.c:new_folio",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_hugetlbs",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270976,
      "name": "folio_test_hugetlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "folio_test_hugetlb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582736145,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:replace_page_cache_folio",
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823442,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582907600,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095474,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:collect_longterm_unpinnable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277882,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349589,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:destroy_large_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583563574,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:get_hwpoison_hugetlb_folio",
        "mm/hugetlb.c:isolate_hugetlb",
        "mm/hugetlb.c:demote_free_hugetlb_folio",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:PageHuge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587245,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_migration_target_by_mpol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583659089,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_hugetlbs",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726146,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851430,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587576197,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587596270,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594370775,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:csum_and_copy_from_iter_full"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594433134,
      "name": "folio_test_hugetlb",
      "external": false,
      "loc": "include/linux/page-flags.h:846",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:csum_and_copy_to_iter"
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
bool folio_test_hugetlb(struct folio * folio)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool folio_test_hugetlb(struct folio * folio)
```
</details>
</li>
</ul>

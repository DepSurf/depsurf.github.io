# Function: <code>PageHeadHuge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580796352,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1311",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": [
        "arch/x86/mm/gup.c:gup_huge_pud",
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "mm/swap.c:__get_page_tail",
        "mm/swap.c:__get_page_tail",
        "mm/swap.c:__get_page_tail",
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_mapped_in_vma",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk",
        "mm/rmap.c:rmap_walk",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796352,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919840,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1338",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_mapped_in_vma",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919840,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987984,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1338",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_mapped_in_vma",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987984,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034416,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1356",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034416,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144160,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1362",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144160,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287264,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1350",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287264,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370176,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1351",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370176,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480992,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1382",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480992,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545408,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545408,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581745282,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1575",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755360,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581822782,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1603",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page",
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803488,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581853009,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1561",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:get_hwpoison_huge_page",
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830800,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582144577,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1752",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:get_hwpoison_huge_page",
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120080,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544736,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1863",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
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
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/folio-compat.c:pagecache_get_page",
        "mm/util.c:folio_mapcount",
        "mm/util.c:folio_mapcount",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
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
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/hugetlb.c:get_hwpoison_huge_page",
        "mm/hugetlb.c:isolate_hugetlb",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/verity/enable.c:read_file_data_page",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
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
      "addr": 18446744071582544736,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061024,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:2059",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:read_cache_page_gfp",
        "mm/filemap.c:read_cache_page",
        "mm/filemap.c:filemap_map_pages",
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
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:unuse_pte",
        "mm/hugetlb.c:get_hwpoison_huge_page",
        "mm/hugetlb.c:isolate_hugetlb",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:folio_migrate_flags",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
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
      "addr": 18446744071583061024,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492979128,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492979128,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "PageHeadHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:578",
      "file": "mm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHeadHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:578",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHeadHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:578",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286399248,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286399248,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272884938,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272884938,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514144,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514144,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456336,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:add_to_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456336,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505456,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505456,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int PageHeadHuge(struct page * page_head)
```

```json
{
  "name": "PageHeadHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570448,
      "name": "PageHeadHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1430",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570448,
      "name": "PageHeadHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int PageHeadHuge(struct page * page_head)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int PageHeadHuge(struct page * page_head)
```
</details>
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

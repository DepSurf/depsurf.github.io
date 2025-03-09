# Function: <code>PageHuge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789408,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1297",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:__put_compound_page",
        "mm/rmap.c:__page_check_address",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:SyS_move_pages",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:put_hwpoison_page",
        "mm/memory-failure.c:put_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789408,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580912304,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1324",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:__basepage_index",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912304,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580980416,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1324",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__basepage_index",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980416,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581032241,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1342",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023328,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581141717,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1348",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:__basepage_index"
      ],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132848,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581304738,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1336",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275840,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581388404,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1337",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358784,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471760,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1368",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471760,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581536016,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536016,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775199,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1561",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:page_cache_delete",
        "mm/swap.c:release_pages",
        "mm/swap.c:__put_page",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/page_alloc.c:pfn_range_valid_contig",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memory_hotplug.c:scan_movable_pages",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:copy_huge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743040,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581823359,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1589",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:page_cache_delete",
        "mm/swap.c:release_pages",
        "mm/util.c:__page_mapcount",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_referenced_one",
        "mm/page_alloc.c:pfn_range_valid_contig",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/swap_state.c:find_get_incore_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:write_protect_page",
        "mm/memory_hotplug.c:scan_movable_pages",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:copy_huge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:isolate_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:__get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791472,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581852625,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1547",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page"
      ],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:release_pages",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/util.c:__page_mapcount",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/swap_state.c:find_get_incore_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags",
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:iov_iter_npages",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iov_iter_gap_alignment",
        "lib/iov_iter.c:iov_iter_alignment",
        "lib/iov_iter.c:iov_iter_advance",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819808,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582144072,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1738",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page"
      ],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:release_pages",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/util.c:__page_mapcount",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_mlock_one",
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
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/rmap.c:page_address_in_vma",
        "mm/rmap.c:page_address_in_vma",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/swap_state.c:find_get_incore_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/page.c:stable_page_flags",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iter_xarray_populate_pages",
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
      "addr": 18446744071582106032,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582597336,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1849",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page"
      ],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/swap.c:__put_page",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/util.c:__page_mapcount",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:vma_address",
        "mm/page_vma_mapped.c:vma_address",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory_hotplug.c:offline_pages",
        "mm/swap_state.c:find_get_incore_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556128,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069408,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:2045",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:rmap_walk_anon",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_address_in_vma",
        "mm/memory_hotplug.c:offline_pages",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069408,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281248,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:2066",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/page_vma_mapped.c:vma_address",
        "mm/rmap.c:vma_address",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:collect_procs_anon",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281248,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517488,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:2166",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/page.c:stable_page_flags",
        "fs/proc/page.c:stable_page_flags",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517488,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492999392,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:alloc_gigantic_page"
      ],
      "caller_func": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492963584,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
  "name": "PageHuge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "PageHuge",
      "external": false,
      "loc": "include/linux/page-flags.h:577",
      "file": "fs/proc/page.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286426556,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286379040,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272900800,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272874714,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504752,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504752,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447056,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447056,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581496064,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496064,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int PageHuge(struct page * page)
```

```json
{
  "name": "PageHuge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581562928,
      "name": "PageHuge",
      "external": true,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:__put_compound_page",
        "mm/util.c:__page_mapcount",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:new_non_cma_page",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__basepage_index",
        "mm/hugetlb.c:__free_huge_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:new_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/page.c:stable_page_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562928,
      "name": "PageHuge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int PageHuge(struct page * page)
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

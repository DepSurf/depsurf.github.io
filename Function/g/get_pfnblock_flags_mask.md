# Function: <code>get_pfnblock_flags_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580499968,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:6435",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/hugetlb.c:dequeue_huge_page_node",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:test_pages_isolated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499968,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580578032,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:395",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/hugetlb.c:dequeue_huge_page_node",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578032,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644576,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:400",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/hugetlb.c:dequeue_huge_page_node",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644576,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580676864,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:416",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580676864,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761616,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:431",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761616,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897600,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:392",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897600,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972208,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:436",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/memory-failure.c:soft_offline_page",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972208,
      "name": "get_pfnblock_flags_mask",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390496,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:498",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390496,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581451456,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451456,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657168,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:484",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657168,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705328,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:488",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705328,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726144,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:510",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726144,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int get_pfnblock_flags_mask(const struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581998976,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:512",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581998976,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
long unsigned int get_pfnblock_flags_mask(const struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582442841,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:502",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page"
      ],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:split_free_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427616,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long unsigned int get_pfnblock_flags_mask(const struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582952007,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:563",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page"
      ],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:split_free_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936320,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long unsigned int get_pfnblock_flags_mask(const struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583168920,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:404",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page"
      ],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:split_free_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153760,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long unsigned int get_pfnblock_flags_mask(const struct page * page, long unsigned int pfn, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583341389,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:372",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:free_pcppages_bulk"
      ],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_find_migrateblock",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:suitable_migration_target",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:put_page_back_buddy",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329712,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492859216,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__free_one_page",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/memory-failure.c:soft_offline_page",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492859216,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226683680,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_pcppages_bulk"
      ],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226662784,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286248560,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286248560,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272804540,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272804540,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420304,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420304,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362816,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362816,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411504,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411504,
      "name": "get_pfnblock_flags_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int get_pfnblock_flags_mask(struct page * page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask)
```

```json
{
  "name": "get_pfnblock_flags_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475680,
      "name": "get_pfnblock_flags_mask",
      "external": true,
      "loc": "mm/page_alloc.c:485",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/shuffle.c:__shuffle_zone",
        "mm/shuffle.c:__shuffle_zone",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475680,
      "name": "get_pfnblock_flags_mask",
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int end_bitidx</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, pfn, end_bitidx, mask</code> ➡️ <code>page, pfn, mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page * page</code> ➡️ <code>const struct page * page</code>
</li>
</ul>
</details>
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

# Function: <code>__next_zones_zonelist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701024,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:55",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701024,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766832,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:55",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766832,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803280,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:55",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803280,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891984,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891984,
      "name": "__next_zones_zonelist",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027968,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027968,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105504,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105504,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170336,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170336,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228368,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228368,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416224,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_zones",
        "mm/vmscan.c:shrink_zones",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416224,
      "name": "__next_zones_zonelist",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459344,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_zones",
        "mm/vmscan.c:shrink_zones",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459344,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480176,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480176,
      "name": "__next_zones_zonelist",
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734640,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734640,
      "name": "__next_zones_zonelist",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115760,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115760,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589600,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589600,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582796960,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796960,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971584,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971584,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492618928,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492618928,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226469696,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226469696,
      "name": "__next_zones_zonelist",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285936384,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:local_memory_node",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285936384,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272644002,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272644002,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197216,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197216,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143968,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143968,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188416,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188416,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "__next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251744,
      "name": "__next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:56",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251744,
      "name": "__next_zones_zonelist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct zoneref * __next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```
</details>
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

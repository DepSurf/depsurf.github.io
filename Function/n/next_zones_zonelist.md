# Function: <code>next_zones_zonelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct zoneref * next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599216,
      "name": "next_zones_zonelist",
      "external": true,
      "loc": "mm/mmzone.c:55",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "fs/buffer.c:free_more_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599216,
      "name": "next_zones_zonelist",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580571894,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580575184,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648503,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754173,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920964,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580948326,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983372,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380463,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:987",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580638626,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580641600,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715634,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819505,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989316,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020758,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057212,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458605,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:961",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580670263,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580674048,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750334,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859955,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025435,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066612,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104934,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514765,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:981",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:free_more_memory"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580755319,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580759408,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580837582,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950947,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141387,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177761,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581219939,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:984",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890298,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580895255,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974263,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087075,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279578,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322590,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361054,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:983",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580964029,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580970055,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050935,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164995,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362106,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406782,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446361,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:991",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581058156,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581114466,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235926,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387910,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473420,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518937,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559574,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1031",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581113916,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581171426,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581294390,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448854,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537439,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583497,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624537,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581292369,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364016,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_zones",
        "mm/vmscan.c:shrink_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484582,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680031,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742641,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795541,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839374,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1021",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581336529,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407616,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_zones",
        "mm/vmscan.c:shrink_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526309,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727775,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791663,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843445,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890814,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1059",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581356225,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428848,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548469,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750141,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820810,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874283,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921390,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1122",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581604081,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681056,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812054,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030045,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106910,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165537,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582217086,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1162",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580780843,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964209,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582057851,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201089,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458168,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545561,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582622754,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582682238,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1183",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581063342,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397329,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582530539,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687757,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972264,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583062729,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583147074,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583210836,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1499",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581153639,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603233,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733979,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897313,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184090,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272966,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583357427,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428919,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1624",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581259618,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774689,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582901899,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069185,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368202,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:wake_all_kswapds",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408805,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_any_partial",
        "mm/slub.c:get_any_partial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583509302,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594050,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1634",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492481904,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492551244,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492700912,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492858424,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492967404,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493021220,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493071332,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226431620,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226539092,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 3226655992,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285767220,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285853744,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286035020,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286278280,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "mm/page_alloc.c:unreserve_highatomic_pageblock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286388260,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286449644,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286513384,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272597432,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272702266,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272802824,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272876990,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581082764,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581140274,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263238,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417702,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506175,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552233,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593273,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581029948,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581087218,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209894,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360214,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448367,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493881,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534713,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581073964,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581131474,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254438,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408902,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497487,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543545,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584585,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
  "name": "next_zones_zonelist",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581135692,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581193938,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318278,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_zonelist_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472998,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564460,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/hugetlb.c:dequeue_huge_page_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608553,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mempolicy_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650224,
      "name": "next_zones_zonelist",
      "external": false,
      "loc": "include/linux/mmzone.h:1038",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct zoneref * next_zones_zonelist(struct zoneref * z, enum zone_type highest_zoneidx, nodemask_t * nodes)
```
</details>
</li>
</ul>

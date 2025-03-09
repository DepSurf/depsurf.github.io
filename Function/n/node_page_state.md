# Function: <code>node_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605856,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:598",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605856,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580704434,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:807",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709104,
      "name": "node_page_state",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580770210,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:807",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774928,
      "name": "node_page_state",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806814,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:807",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811376,
      "name": "node_page_state",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580895970,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:991",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901376,
      "name": "node_page_state",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581031784,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:991",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037200,
      "name": "node_page_state",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581109357,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:991",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114784,
      "name": "node_page_state",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581174118,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179440,
      "name": "node_page_state",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581232214,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237552,
      "name": "node_page_state",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581418933,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426352,
      "name": "node_page_state",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469664,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1017",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469664,
      "name": "node_page_state",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490400,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1029",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490400,
      "name": "node_page_state",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749056,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1035",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749056,
      "name": "node_page_state",
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
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582131328,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1036",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131328,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606928,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1023",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606928,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815616,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1024",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:si_meminfo_node",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815616,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990096,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:1027",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:lru_gen_shrink_node",
        "mm/vmscan.c:lru_gen_shrink_node",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:si_meminfo_node",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990096,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492621768,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492632920,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285942084,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285950320,
      "name": "node_page_state",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581201062,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206400,
      "name": "node_page_state",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581147814,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153152,
      "name": "node_page_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581192262,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197600,
      "name": "node_page_state",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581255542,
      "name": "node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:992",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print"
      ],
      "caller_func": [
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/page-writeback.c:node_dirty_ok",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:node_pagecache_reclaimable",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_meminfo_node",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260880,
      "name": "node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pglist_data * pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>int node</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum zone_stat_item item</code> ➡️ <code>enum node_stat_item item</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int node_page_state(struct pglist_data * pgdat, enum node_stat_item item)
```
</details>
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

# Function: <code>next_online_pgdat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599088,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:17",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599088,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700896,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:17",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700896,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766704,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:17",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766704,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803152,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:17",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803152,
      "name": "next_online_pgdat",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891856,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891856,
      "name": "next_online_pgdat",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027840,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/nobootmem.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027840,
      "name": "next_online_pgdat",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105376,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105376,
      "name": "next_online_pgdat",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170208,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170208,
      "name": "next_online_pgdat",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228240,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228240,
      "name": "next_online_pgdat",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581416141,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416032,
      "name": "next_online_pgdat",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459261,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459152,
      "name": "next_online_pgdat",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581480093,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479984,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581734557,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:warn_alloc",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734448,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582115647,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:warn_alloc",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115472,
      "name": "next_online_pgdat",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582589495,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:warn_alloc",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:__show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589344,
      "name": "next_online_pgdat",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582796855,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:warn_alloc",
        "mm/memblock.c:reset_all_zones_managed_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796704,
      "name": "next_online_pgdat",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582971479,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmzone.c:next_zone"
      ],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:warn_alloc",
        "mm/memblock.c:reset_all_zones_managed_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971328,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492618744,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492618744,
      "name": "next_online_pgdat",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226469624,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226469624,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285936160,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285936160,
      "name": "next_online_pgdat",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272643912,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272643912,
      "name": "next_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197088,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197088,
      "name": "next_online_pgdat",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143840,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143840,
      "name": "next_online_pgdat",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188288,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188288,
      "name": "next_online_pgdat",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pglist_data * next_online_pgdat(struct pglist_data * pgdat)
```

```json
{
  "name": "next_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251616,
      "name": "next_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:18",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmzone.c:next_zone",
        "mm/vmstat.c:frag_next",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251616,
      "name": "next_online_pgdat",
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

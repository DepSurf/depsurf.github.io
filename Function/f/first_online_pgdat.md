# Function: <code>first_online_pgdat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599024,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:12",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:snapshot_write_next",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:init_per_zone_wmark_min",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:drain_pages",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "fs/proc/meminfo.c:meminfo_proc_show",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599024,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700832,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:12",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700832,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766640,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:12",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766640,
      "name": "first_online_pgdat",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803088,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:12",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/madvise.c:SyS_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803088,
      "name": "first_online_pgdat",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891792,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/madvise.c:SyS_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891792,
      "name": "first_online_pgdat",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027776,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/nobootmem.c:reset_all_zones_managed_pages",
        "mm/madvise.c:madvise_inject_error",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027776,
      "name": "first_online_pgdat",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105312,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:madvise_inject_error",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105312,
      "name": "first_online_pgdat",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170144,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170144,
      "name": "first_online_pgdat",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228176,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228176,
      "name": "first_online_pgdat",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415968,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:__setup_per_zone_wmarks",
        "mm/page_alloc.c:__setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:madvise_inject_error",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415968,
      "name": "first_online_pgdat",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459088,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:__setup_per_zone_wmarks",
        "mm/page_alloc.c:__setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459088,
      "name": "first_online_pgdat",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479936,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_local_pages_wq",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479936,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734400,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_local_pages_wq",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/memory_hotplug.c:auto_movable_can_online_movable",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734400,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115408,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_local_pages_wq",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/memory_hotplug.c:auto_movable_can_online_movable",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115408,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589264,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:__show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_local_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/memory_hotplug.c:auto_movable_can_online_movable",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process",
        "lib/show_mem.c:__show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589264,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582796624,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/mm_init.c:page_alloc_init_late",
        "mm/show_mem.c:__show_mem",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:__show_free_areas",
        "mm/show_mem.c:si_mem_available",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_local_pages",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/memory_hotplug.c:auto_movable_can_online_movable",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796624,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971248,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:create_mem_extents",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:fold_vm_numa_events",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/mm_init.c:page_alloc_init_late",
        "mm/show_mem.c:__show_mem",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:show_free_areas",
        "mm/show_mem.c:si_mem_available",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:page_alloc_cpu_online",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:page_alloc_cpu_dead",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_pcp_cacheinfo",
        "mm/page_alloc.c:warn_alloc",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:__drain_all_pages",
        "mm/page_alloc.c:drain_local_pages",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/memory_hotplug.c:auto_movable_can_online_movable",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/khugepaged.c:set_recommended_min_free_kbytes",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971248,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492618672,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492618672,
      "name": "first_online_pgdat",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226469592,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:count_highmem_pages",
        "kernel/power/snapshot.c:count_free_highmem_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/highmem.c:nr_free_highpages",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:__setup_per_zone_wmarks",
        "mm/page_alloc.c:__setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226469592,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285936048,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__se_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285936048,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272643878,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272643878,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197024,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197024,
      "name": "first_online_pgdat",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143776,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143776,
      "name": "first_online_pgdat",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188224,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188224,
      "name": "first_online_pgdat",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pglist_data * first_online_pgdat()
```

```json
{
  "name": "first_online_pgdat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251552,
      "name": "first_online_pgdat",
      "external": true,
      "loc": "mm/mmzone.c:13",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:count_data_pages",
        "kernel/power/snapshot.c:memory_bm_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:frag_start",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_slab_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_min_unmapped_ratio",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_lowmem_reserve",
        "mm/page_alloc.c:calculate_totalreserve_pages",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:setup_per_cpu_pageset",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:si_mem_available",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:drain_pages",
        "mm/page_alloc.c:page_alloc_init_late",
        "mm/memblock.c:reset_all_zones_managed_pages",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:start_stop_khugepaged",
        "lib/show_mem.c:show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251552,
      "name": "first_online_pgdat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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

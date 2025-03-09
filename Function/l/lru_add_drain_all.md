# Function: <code>lru_add_drain_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541472,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:870",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:SyS_mlockall",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:SyS_move_pages",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541472,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629968,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:689",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:SyS_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memory-failure.c:shake_page",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629968,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697184,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:690",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memory-failure.c:shake_page",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697184,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731392,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:727",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731392,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817440,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:727",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817440,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:671",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_fcntl",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955194,
      "name": "lru_add_drain_all.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580954032,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:667",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:kernel_move_pages",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_fcntl",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031386,
      "name": "lru_add_drain_all.cold.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581030224,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:668",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095389,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071581094224,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152314,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581151184,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:762",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338154,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581337072,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:748",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/memory_hotplug.c:offline_pages",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325280,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581378192,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399504,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:848",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399504,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650096,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:839",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:compact_store",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "block/bdev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650096,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018976,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:847",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:compact_store",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018976,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454144,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:937",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:compact_store",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454144,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659344,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:903",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:compact_store",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659344,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830464,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:903",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:compact_store",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:get_any_page",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "block/bdev.c:bdev_mark_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830464,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492527904,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492527904,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226395088,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_do_scan",
        "mm/migrate.c:migrate_prep",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226395088,
      "name": "lru_add_drain_all",
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285822464,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285822464,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272581470,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_do_scan",
        "mm/migrate.c:migrate_prep",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272581470,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121162,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581120032,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068154,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581067024,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112362,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581111232,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void lru_add_drain_all()
```

```json
{
  "name": "lru_add_drain_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lru_add_drain_all",
      "external": true,
      "loc": "mm/swap.c:709",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/compaction.c:sysfs_compact_node",
        "mm/compaction.c:sysctl_compaction_handler",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/block_dev.c:invalidate_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174842,
      "name": "lru_add_drain_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581173712,
      "name": "lru_add_drain_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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

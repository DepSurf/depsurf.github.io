# Function: <code>inc_node_page_state</code>

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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701424,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:511",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SyS_move_pages",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701424,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772624,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:511",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SYSC_move_pages",
        "mm/khugepaged.c:khugepaged",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772624,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809072,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:511",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SYSC_move_pages",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809072,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898256,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:586",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/khugepaged.c:khugepaged",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898256,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034160,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:586",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034160,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111728,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:586",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111728,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176432,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176432,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234560,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234560,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423456,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423456,
      "name": "inc_node_page_state",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464912,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:601",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:isolate_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464912,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487024,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:613",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:__soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487024,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741024,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:659",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout",
        "mm/memory-failure.c:__soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741024,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122560,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:688",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:__soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122560,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599008,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:675",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_in_use_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599008,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804720,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:676",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804720,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982368,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:677",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:do_migrate_range",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982368,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492626496,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492626496,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226477032,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:656",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226477032,
      "name": "inc_node_page_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285948096,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:656",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285948096,
      "name": "inc_node_page_state",
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272651066,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:656",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272651066,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203408,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203408,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150160,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150160,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194608,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194608,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257888,
      "name": "inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:587",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257888,
      "name": "inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void inc_node_page_state(struct page * page, enum node_stat_item item)
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

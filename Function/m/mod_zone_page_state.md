# Function: <code>mod_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603696,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:359",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:free_area_init_node",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/compaction.c:acct_isolated",
        "mm/compaction.c:acct_isolated",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:mlock_vma_page",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603696,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706256,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:442",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706256,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772192,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:442",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772192,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808656,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:442",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808656,
      "name": "mod_zone_page_state",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897840,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:517",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897840,
      "name": "mod_zone_page_state",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033744,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:517",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033744,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111312,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:517",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111312,
      "name": "mod_zone_page_state",
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176016,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176016,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234144,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234144,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421216,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421216,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464320,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:527",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464320,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485168,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:533",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485168,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741216,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:579",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741216,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122800,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:608",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned",
        "mm/swap.c:__page_cache_release",
        "mm/mlock.c:mlock_new_page",
        "mm/mlock.c:mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122800,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597376,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:595",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/mlock.c:mlock_new_page",
        "mm/mlock.c:mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597376,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805008,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:596",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/mlock.c:mlock_new_folio",
        "mm/mlock.c:mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805008,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979584,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:596",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:folio_account_cleaned",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/mlock.c:mlock_new_folio",
        "mm/mlock.c:mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979584,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492626176,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492626176,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226474760,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:602",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226474760,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285937760,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:602",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285937760,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272644866,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:602",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272644866,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581202992,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202992,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149744,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149744,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194192,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194192,
      "name": "mod_zone_page_state",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257472,
      "name": "mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:518",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257472,
      "name": "mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
